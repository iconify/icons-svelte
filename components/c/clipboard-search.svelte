<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/icz0-ubxj.css';
import '../../css/s/sj2jncbna.css';
import '../../css/o/odm-58bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="icz0-ubxj"/><path class="sj2jncbna"/><path class="odm-58bur"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:clipboard-search" {...props}></Icon>
