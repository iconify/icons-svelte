<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkozv6_ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkozv6_ko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazonsqs" {...props}></Icon>
