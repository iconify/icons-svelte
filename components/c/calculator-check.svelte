<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2lnp2nzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2lnp2nzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:calculator-check" {...props}></Icon>
