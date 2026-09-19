<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlshrtbyk.css';
import '../../css/m/m8-q3inzh.css';
import '../../css/c/c3b89bbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mlshrtbyk"/><path class="m8-q3inzh"/><path class="c3b89bbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-podium" {...props}></Icon>
