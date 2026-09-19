<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emos5l7br.css';
import '../../css/z/zp9iurb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emos5l7br"/><path class="zp9iurb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-bottom-alt" {...props}></Icon>
