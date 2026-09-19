<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cci33jb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cci33jb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:comment" {...props}></Icon>
