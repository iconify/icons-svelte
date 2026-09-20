<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cynbbq5ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cynbbq5ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:arrange-bring-to-front" {...props}></Icon>
