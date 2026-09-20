<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acmnv-6wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acmnv-6wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:curly-braces" {...props}></Icon>
