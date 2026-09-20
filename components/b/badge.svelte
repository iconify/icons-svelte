<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm7spf6mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm7spf6mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:badge" {...props}></Icon>
