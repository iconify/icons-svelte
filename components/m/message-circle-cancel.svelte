<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8hbi9srx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8hbi9srx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle-cancel" {...props}></Icon>
