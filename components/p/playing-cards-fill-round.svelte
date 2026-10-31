<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq89u5v2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq89u5v2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:playing-cards-fill-round" {...props}></Icon>
