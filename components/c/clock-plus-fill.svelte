<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e030fm8ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e030fm8ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-plus-fill" {...props}></Icon>
