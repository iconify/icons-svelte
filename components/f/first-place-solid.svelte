<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v69qzzb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v69qzzb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:first-place-solid" {...props}></Icon>
