<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htktd2baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htktd2baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:castle-star" {...props}></Icon>
