<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jth1l4h1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jth1l4h1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:facebook-messenger-alt" {...props}></Icon>
