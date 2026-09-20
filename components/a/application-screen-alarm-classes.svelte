<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp7u0ab4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mp7u0ab4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:application-screen-alarm-classes" {...props}></Icon>
