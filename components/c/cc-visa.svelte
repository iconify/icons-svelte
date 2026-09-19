<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_vv43bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q_vv43bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cc-visa" {...props}></Icon>
