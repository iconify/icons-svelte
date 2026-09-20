<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/e/ecjyiacqx.css';
import '../../css/i/i8r_mr_be.css';
import '../../css/x/x-fkqvbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><rect class="ecjyiacqx"/><rect class="i8r_mr_be"/><path class="x-fkqvbof"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:headphones-fill" {...props}></Icon>
