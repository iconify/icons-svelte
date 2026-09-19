<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4yqyt6tg.css';
import '../../css/n/nnl6f83rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":24};
const content = `<path class="e4yqyt6tg"/><path class="nnl6f83rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:jira" {...props}></Icon>
