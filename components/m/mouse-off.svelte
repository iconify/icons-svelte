<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1mq-0jsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1mq-0jsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mouse-off" {...props}></Icon>
