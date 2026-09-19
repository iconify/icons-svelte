<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbwchz17z.css';
import '../../css/j/j8n5sacrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbwchz17z"/><path class="j8n5sacrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:prawn" {...props}></Icon>
