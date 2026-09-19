<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt2b1obqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt2b1obqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:left-arrow-alt" {...props}></Icon>
