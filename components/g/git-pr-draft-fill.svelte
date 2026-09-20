<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqvkq1msn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqvkq1msn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-pr-draft-fill" {...props}></Icon>
