<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck5hzwv6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ck5hzwv6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:gift-top-20-solid" {...props}></Icon>
