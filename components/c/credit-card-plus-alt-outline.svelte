<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1lsw24hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1lsw24hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:credit-card-plus-alt-outline" {...props}></Icon>
