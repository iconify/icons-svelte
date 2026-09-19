<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsxvbkbsh.css';
import '../../css/n/nu2_-nbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bsxvbkbsh"/><path class="nu2_-nbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-person" {...props}></Icon>
