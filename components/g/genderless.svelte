<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp-6wrbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":288,"height":512};
const content = `<path class="cp-6wrbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:genderless" {...props}></Icon>
