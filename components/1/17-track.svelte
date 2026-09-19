<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvn6v2bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvn6v2bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:17-track" {...props}></Icon>
