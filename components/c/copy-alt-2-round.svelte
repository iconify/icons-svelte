<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb_0hvarj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb_0hvarj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:copy-alt-2-round" {...props}></Icon>
