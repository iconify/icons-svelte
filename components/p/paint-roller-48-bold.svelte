<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5xe2hu9u.css';
import '../../css/q/qxn5niypj.css';
import '../../css/m/mrnim2byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e5xe2hu9u"/><path class="qxn5niypj"/><path class="mrnim2byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paint-roller-48-bold" {...props}></Icon>
