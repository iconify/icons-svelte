<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj0mq3b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj0mq3b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:database-line" {...props}></Icon>
