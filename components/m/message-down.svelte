<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qln0q4btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qln0q4btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-down" {...props}></Icon>
