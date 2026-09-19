<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0mq3zi8m.css';
import '../../css/j/jvh2qfzit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0mq3zi8m"/><path class="jvh2qfzit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:handheld-alt" {...props}></Icon>
