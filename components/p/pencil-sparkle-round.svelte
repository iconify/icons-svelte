<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7gsaub5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7gsaub5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-sparkle-round" {...props}></Icon>
