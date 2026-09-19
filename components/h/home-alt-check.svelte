<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8qr_m7mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8qr_m7mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:home-alt-check" {...props}></Icon>
