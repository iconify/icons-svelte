<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/non9dj5qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="non9dj5qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-left-up" {...props}></Icon>
