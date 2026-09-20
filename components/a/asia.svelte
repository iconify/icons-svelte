<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/ec82zvbgj.css';
import '../../css/d/dorfjocjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ec82zvbgj"/><path class="dorfjocjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:asia" {...props}></Icon>
