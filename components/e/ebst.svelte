<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoay7kesa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yoay7kesa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ebst" {...props}></Icon>
