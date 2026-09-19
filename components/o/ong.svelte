<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb5ck8ldz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lb5ck8ldz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ong" {...props}></Icon>
