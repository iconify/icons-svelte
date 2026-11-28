<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_ts1cluy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_ts1cluy primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-off-duotone" {...props}></Icon>
