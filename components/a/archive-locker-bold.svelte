<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2swubccs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2swubccs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:archive-locker-bold" {...props}></Icon>
