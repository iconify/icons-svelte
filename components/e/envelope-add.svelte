<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7fm78wil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7fm78wil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-add" {...props}></Icon>
