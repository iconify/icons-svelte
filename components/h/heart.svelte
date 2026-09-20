<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax0vc5bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax0vc5bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:heart" {...props}></Icon>
