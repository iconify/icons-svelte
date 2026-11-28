<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqiz-dwfi.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/spokbjbne.css';
import '../../css/r/raewjx2vl.css';
import '../../css/c/cvitlkb7d.css';
import '../../css/m/mwrf1aclp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary vqiz-dwfi"/><g class="dt0cm9dhy primary"><path class="spokbjbne"/><path class="raewjx2vl"/><path class="cvitlkb7d"/><path class="mwrf1aclp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:earth-duo" {...props}></Icon>
