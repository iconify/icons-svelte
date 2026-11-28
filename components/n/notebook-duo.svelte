<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj3gkuzfe.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qr_-isbgg.css';
import '../../css/c/c5__r9abd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj3gkuzfe secondary"/><g class="dt0cm9dhy primary"><path class="qr_-isbgg"/><path class="c5__r9abd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:notebook-duo" {...props}></Icon>
