<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl3cvobbt.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l24zqccfl.css';
import '../../css/q/qiuzifbed.css';
import '../../css/q/q6vbnacif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl3cvobbt secondary"/><g class="dt0cm9dhy primary"><path class="l24zqccfl"/><path class="qiuzifbed"/><path class="q6vbnacif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:lamp-desk-duo" {...props}></Icon>
