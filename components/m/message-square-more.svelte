<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2mv7oq0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2mv7oq0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:message-square-more" {...props}></Icon>
