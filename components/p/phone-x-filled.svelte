<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouv-3on5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouv-3on5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-x-filled" {...props}></Icon>
