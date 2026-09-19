<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sry2f1b9n.css';
import '../../css/g/g8_-9ibpo.css';
import '../../css/u/u7kjvobou.css';
import '../../css/k/kpz46-vtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="sry2f1b9n"/><path class="g8_-9ibpo"/><path class="u7kjvobou"/><path class="kpz46-vtn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:clipboard" {...props}></Icon>
