<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plpwqubjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="plpwqubjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:arrow-alt-circle-up" {...props}></Icon>
