<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehqy8dbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehqy8dbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-big-left-dash" {...props}></Icon>
