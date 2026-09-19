<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twkmy8jve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twkmy8jve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-user-detail" {...props}></Icon>
