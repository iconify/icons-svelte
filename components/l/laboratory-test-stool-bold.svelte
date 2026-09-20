<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0x7g52ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0x7g52ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:laboratory-test-stool-bold" {...props}></Icon>
