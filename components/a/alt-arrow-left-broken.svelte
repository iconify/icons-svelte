<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcj4w92ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcj4w92ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-left-broken" {...props}></Icon>
