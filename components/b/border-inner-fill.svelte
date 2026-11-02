<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glkt4nbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glkt4nbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-inner-fill" {...props}></Icon>
