<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bn340ib1t.css';
import '../../css/h/hu30fdbrj.css';
import '../../css/b/b-nnx4bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bn340ib1t"/><path class="hu30fdbrj"/><path class="b-nnx4bkp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-up-linear" {...props}></Icon>
