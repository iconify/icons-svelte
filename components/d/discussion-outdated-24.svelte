<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oabydjbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oabydjbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:discussion-outdated-24" {...props}></Icon>
