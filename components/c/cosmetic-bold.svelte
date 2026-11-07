<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9cb8qbxu.css';
import '../../css/d/d7n_wt5my.css';
import '../../css/c/cxt5hpr-p.css';
import '../../css/s/scepf5ivk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9cb8qbxu"/><path class="d7n_wt5my"/><path class="cxt5hpr-p"/><path class="scepf5ivk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cosmetic-bold" {...props}></Icon>
