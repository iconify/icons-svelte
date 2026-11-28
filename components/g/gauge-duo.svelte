<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e73euiyzf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rch4b20wr.css';
import '../../css/f/fol11_ihm.css';
import '../../css/v/vu7kjj19z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e73euiyzf secondary"/><g class="dt0cm9dhy primary"><path class="rch4b20wr"/><path class="fol11_ihm"/><path class="vu7kjj19z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gauge-duo" {...props}></Icon>
