<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv5wk7tjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv5wk7tjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ice-cream-off" {...props}></Icon>
