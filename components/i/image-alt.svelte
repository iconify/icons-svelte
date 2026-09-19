<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu56ptb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu56ptb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:image-alt" {...props}></Icon>
