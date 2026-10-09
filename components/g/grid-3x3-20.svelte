<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewn1ke3br.css';
import '../../css/e/euk2bdbjj.css';
import '../../css/c/cdid3gb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewn1ke3br"/><path class="euk2bdbjj"/><path class="cdid3gb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-3x3-20" {...props}></Icon>
