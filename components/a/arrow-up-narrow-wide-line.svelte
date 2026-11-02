<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh2wxxbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh2wxxbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-up-narrow-wide-line" {...props}></Icon>
