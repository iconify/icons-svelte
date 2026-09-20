<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eupidrbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eupidrbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-thick-circle-left-2-bold" {...props}></Icon>
