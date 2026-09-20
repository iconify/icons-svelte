<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi2yjf4ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi2yjf4ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:command-2" {...props}></Icon>
