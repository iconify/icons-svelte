<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh2ook0ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh2ook0ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cutter" {...props}></Icon>
