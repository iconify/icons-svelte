<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfaayzmqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mfaayzmqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-7-fill" {...props}></Icon>
