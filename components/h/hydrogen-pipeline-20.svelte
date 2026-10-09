<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdfjzcrhz.css';
import '../../css/i/iyeej1bps.css';
import '../../css/v/vageni_ng.css';
import '../../css/c/cdv2l9bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kdfjzcrhz"/><path class="iyeej1bps"/><path class="vageni_ng"/><path class="cdv2l9bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-pipeline-20" {...props}></Icon>
