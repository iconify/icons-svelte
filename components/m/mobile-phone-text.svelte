<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a40icebkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a40icebkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mobile-phone-text" {...props}></Icon>
