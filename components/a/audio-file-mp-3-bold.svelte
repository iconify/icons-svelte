<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr2q03bgv.css';
import '../../css/z/z00ni0b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr2q03bgv"/><path class="z00ni0b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:audio-file-mp-3-bold" {...props}></Icon>
