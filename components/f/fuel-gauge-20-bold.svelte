<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e75-znlde.css';
import '../../css/m/mx7qgn1xx.css';
import '../../css/q/qviq0ilhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e75-znlde"/><path class="mx7qgn1xx"/><path class="qviq0ilhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-gauge-20-bold" {...props}></Icon>
