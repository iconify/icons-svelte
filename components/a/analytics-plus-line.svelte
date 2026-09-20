<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx_emh9lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx_emh9lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:analytics-plus-line" {...props}></Icon>
