<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq77azrkm.css';
import '../../css/o/oykk7m8it.css';
import '../../css/q/qkfd58nsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hq77azrkm"/><path class="oykk7m8it"/><path class="qkfd58nsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hi-vis-vest-20" {...props}></Icon>
