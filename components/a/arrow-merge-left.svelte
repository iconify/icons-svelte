<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weqf-9bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="weqf-9bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-merge-left" {...props}></Icon>
