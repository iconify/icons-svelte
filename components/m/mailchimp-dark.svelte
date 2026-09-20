<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luyo9rbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="luyo9rbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailchimp-dark" {...props}></Icon>
