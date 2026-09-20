<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o07pescwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o07pescwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:hulu-live-tv-logo-block" {...props}></Icon>
