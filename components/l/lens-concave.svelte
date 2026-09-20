<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1omq012l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1omq012l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:lens-concave" {...props}></Icon>
