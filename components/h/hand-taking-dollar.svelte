<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juc-fzbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juc-fzbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:hand-taking-dollar" {...props}></Icon>
