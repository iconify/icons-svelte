<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se3k9k9su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="se3k9k9su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-in-fill-12" {...props}></Icon>
