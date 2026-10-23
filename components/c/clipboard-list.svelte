<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1s14pnwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1s14pnwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:clipboard-list" {...props}></Icon>
