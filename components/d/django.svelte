<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lps2qmi-k.css';
import '../../css/h/hx8_3wb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lps2qmi-k"/><path class="hx8_3wb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:django" {...props}></Icon>
