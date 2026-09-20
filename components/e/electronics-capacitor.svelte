<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5tye3v9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5tye3v9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:electronics-capacitor" {...props}></Icon>
