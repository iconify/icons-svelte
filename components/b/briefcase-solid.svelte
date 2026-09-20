<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2-p4bcnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2-p4bcnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:briefcase-solid" {...props}></Icon>
