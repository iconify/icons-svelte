<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp7wmigin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bp7wmigin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:redirect" {...props}></Icon>
