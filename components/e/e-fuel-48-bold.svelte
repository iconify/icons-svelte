<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g21_8vbpp.css';
import '../../css/v/v-zb6dbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g21_8vbpp"/><path class="v-zb6dbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:e-fuel-48-bold" {...props}></Icon>
