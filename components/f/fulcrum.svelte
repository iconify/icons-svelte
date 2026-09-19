<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyef6ab9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="vyef6ab9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:fulcrum" {...props}></Icon>
