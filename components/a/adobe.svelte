<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb8skhyob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb8skhyob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:adobe" {...props}></Icon>
