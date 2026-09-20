<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-se2ybuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-se2ybuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:national-grid" {...props}></Icon>
