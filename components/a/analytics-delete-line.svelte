<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oru5bnb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oru5bnb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:analytics-delete-line" {...props}></Icon>
