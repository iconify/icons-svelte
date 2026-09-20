<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phc95vc3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phc95vc3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bing-logo-2" {...props}></Icon>
