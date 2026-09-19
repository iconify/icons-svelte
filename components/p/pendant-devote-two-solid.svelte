<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4pperbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4pperbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pendant-devote-two-solid" {...props}></Icon>
