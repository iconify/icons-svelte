<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udnvt1-ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udnvt1-ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:instagram-alt" {...props}></Icon>
