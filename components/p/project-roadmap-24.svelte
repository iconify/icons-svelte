<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqq61kbnt.css';
import '../../css/t/tbcp7-bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqq61kbnt"/><path class="tbcp7-bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:project-roadmap-24" {...props}></Icon>
