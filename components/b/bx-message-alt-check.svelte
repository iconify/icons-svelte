<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf3ox7bam.css';
import '../../css/z/z8-dohb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf3ox7bam"/><path class="z8-dohb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-message-alt-check" {...props}></Icon>
