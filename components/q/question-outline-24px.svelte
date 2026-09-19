<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv7h-h8kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv7h-h8kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:question-outline-24px" {...props}></Icon>
