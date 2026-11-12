<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c30cjjbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c30cjjbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-key" {...props}></Icon>
