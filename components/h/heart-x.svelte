<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzor5qb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzor5qb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heart-x" {...props}></Icon>
