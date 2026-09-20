<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evsio0edl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evsio0edl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:link" {...props}></Icon>
