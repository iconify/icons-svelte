<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwq3slbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwq3slbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrange-letter" {...props}></Icon>
