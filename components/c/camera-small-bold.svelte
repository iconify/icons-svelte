<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph8967bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ph8967bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:camera-small-bold" {...props}></Icon>
