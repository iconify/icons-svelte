<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5nyh0bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5nyh0bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-dollar" {...props}></Icon>
