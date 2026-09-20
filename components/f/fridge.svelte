<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgbva3b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qgbva3b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:fridge" {...props}></Icon>
