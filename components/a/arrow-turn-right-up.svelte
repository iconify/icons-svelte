<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s630meb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s630meb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-right-up" {...props}></Icon>
