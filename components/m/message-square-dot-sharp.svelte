<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhq4wvv6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhq4wvv6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-dot-sharp" {...props}></Icon>
