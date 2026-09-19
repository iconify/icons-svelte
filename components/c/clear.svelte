<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsd9cfbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":768};
const content = `<path class="rsd9cfbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:clear" {...props}></Icon>
