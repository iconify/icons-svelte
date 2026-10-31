<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyrdaub_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyrdaub_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:blockquote-duotone-round" {...props}></Icon>
