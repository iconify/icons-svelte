<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qytbqacqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qytbqacqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:quora" {...props}></Icon>
