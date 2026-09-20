<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpk8_q57l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpk8_q57l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:design-tool-ink-bold" {...props}></Icon>
