<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4sxbkezq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p4sxbkezq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:component-carousel-list" {...props}></Icon>
