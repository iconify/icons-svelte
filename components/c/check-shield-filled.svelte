<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv34kebtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv34kebtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:check-shield-filled" {...props}></Icon>
