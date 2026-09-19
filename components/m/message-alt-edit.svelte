<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0xpv8ejv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0xpv8ejv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-alt-edit" {...props}></Icon>
