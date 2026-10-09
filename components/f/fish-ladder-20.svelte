<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qae_zubij.css';
import '../../css/s/stlnhm10c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qae_zubij"/><path class="stlnhm10c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fish-ladder-20" {...props}></Icon>
