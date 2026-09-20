<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-e7r8qso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-e7r8qso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:message-circle-x" {...props}></Icon>
