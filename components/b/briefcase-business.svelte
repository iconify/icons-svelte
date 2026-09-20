<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8ttckkzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8ttckkzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:briefcase-business" {...props}></Icon>
