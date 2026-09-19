<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k371edcsm.css';
import '../../css/a/acjllyibf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k371edcsm"/><path class="acjllyibf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:badge-info" {...props}></Icon>
