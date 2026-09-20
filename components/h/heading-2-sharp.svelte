<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9-qrgs5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9-qrgs5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heading-2-sharp" {...props}></Icon>
