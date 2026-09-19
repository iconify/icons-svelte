<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brjgsq-7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brjgsq-7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-back-fill" {...props}></Icon>
