<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no8yeybbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="no8yeybbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-y-filled" {...props}></Icon>
