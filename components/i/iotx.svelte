<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mysn31kjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mysn31kjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:iotx" {...props}></Icon>
