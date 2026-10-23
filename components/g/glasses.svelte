<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwlijj-zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwlijj-zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:glasses" {...props}></Icon>
