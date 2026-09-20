<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxfhqtdxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxfhqtdxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:archive-of-our-own" {...props}></Icon>
