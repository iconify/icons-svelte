<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovjgg_gxh.css';
import '../../css/p/psfb6tk7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary ovjgg_gxh"/><path class="psfb6tk7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-auditbeat" {...props}></Icon>
