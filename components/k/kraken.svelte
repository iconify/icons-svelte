<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfzjyi6-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<path class="mfzjyi6-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kraken" {...props}></Icon>
