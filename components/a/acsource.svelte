<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb6jb7bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tb6jb7bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:acsource" {...props}></Icon>
