<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9247wbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9247wbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lapce" {...props}></Icon>
