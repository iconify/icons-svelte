<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emos5l7br.css';
import '../../css/d/dn42tbchj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emos5l7br"/><path class="dn42tbchj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-left-alt" {...props}></Icon>
