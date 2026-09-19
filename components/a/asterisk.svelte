<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrzqhjbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrzqhjbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:asterisk" {...props}></Icon>
