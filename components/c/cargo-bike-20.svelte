<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu01-jbtn.css';
import '../../css/r/rspsi8b7x.css';
import '../../css/g/ganklmxwt.css';
import '../../css/e/etikf8b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vu01-jbtn"/><path class="rspsi8b7x"/><path class="ganklmxwt"/><path class="etikf8b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cargo-bike-20" {...props}></Icon>
