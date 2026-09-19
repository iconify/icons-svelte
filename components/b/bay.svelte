<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/munw0bbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="munw0bbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bay" {...props}></Icon>
