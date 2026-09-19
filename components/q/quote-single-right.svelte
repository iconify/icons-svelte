<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr4oekb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr4oekb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:quote-single-right" {...props}></Icon>
