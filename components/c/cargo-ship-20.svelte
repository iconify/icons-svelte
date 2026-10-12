<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hryueux2x.css';
import '../../css/g/gmupky7wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hryueux2x"/><path class="gmupky7wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cargo-ship-20" {...props}></Icon>
