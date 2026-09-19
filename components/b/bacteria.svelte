<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/viaa6ubuw.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/x/xprwyhbwt.css';
import '../../css/k/ks7bf8bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="viaa6ubuw"/><circle class="shu3xdl9q"/><circle class="xprwyhbwt"/><path class="ks7bf8bjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bacteria" {...props}></Icon>
