<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp3_6hbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kp3_6hbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:nav" {...props}></Icon>
