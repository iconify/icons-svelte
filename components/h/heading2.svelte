<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqdujhhlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqdujhhlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heading2" {...props}></Icon>
