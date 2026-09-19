<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buv1006ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buv1006ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:lightning-1-light" {...props}></Icon>
