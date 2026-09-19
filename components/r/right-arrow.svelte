<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr9zrtbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr9zrtbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:right-arrow" {...props}></Icon>
