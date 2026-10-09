<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn86vr-5u.css';
import '../../css/h/hjs-1h8-e.css';
import '../../css/v/v4b84_btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gn86vr-5u"/><path class="hjs-1h8-e"/><path class="v4b84_btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offset-48-bold" {...props}></Icon>
