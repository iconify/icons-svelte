<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd5jr6i4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd5jr6i4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:programming-language-html-5-bold" {...props}></Icon>
