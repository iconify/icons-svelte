<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irgq9rb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irgq9rb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:heading-2" {...props}></Icon>
