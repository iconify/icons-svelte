<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_gnyab1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_gnyab1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:code-2-filled" {...props}></Icon>
