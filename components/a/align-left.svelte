<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/c/crv4i00bu.css';
import '../../css/f/f120vrbmk.css';
import '../../css/i/il9ursnxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="crv4i00bu"/><rect class="f120vrbmk"/><rect class="il9ursnxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:align-left" {...props}></Icon>
