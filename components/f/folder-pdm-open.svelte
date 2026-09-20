<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vphu21bda.css';
import '../../css/q/qcal1ccqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vphu21bda"/><path class="qcal1ccqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-pdm-open" {...props}></Icon>
