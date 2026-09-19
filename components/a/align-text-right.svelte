<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y27pmdbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y27pmdbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:align-text-right" {...props}></Icon>
