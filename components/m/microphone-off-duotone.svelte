<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/axs4e-b7g.css';
import '../../css/a/ae1d9obmw.css';
import '../../css/n/n35dlibfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="axs4e-b7g"/><path class="ae1d9obmw"/><path class="n35dlibfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:microphone-off-duotone" {...props}></Icon>
