<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfz3w9lrl.css';
import '../../css/n/n_mcnmbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="yfz3w9lrl"/><path class="n_mcnmbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:body" {...props}></Icon>
