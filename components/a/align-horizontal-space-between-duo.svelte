<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2q8uqztx.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uwst6zbsv.css';
import '../../css/y/ywhlzacjl.css';
import '../../css/c/cg66pc8qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2q8uqztx secondary"/><g class="dt0cm9dhy primary"><path class="uwst6zbsv"/><path class="ywhlzacjl"/><path class="cg66pc8qp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:align-horizontal-space-between-duo" {...props}></Icon>
