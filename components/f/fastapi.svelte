<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_89xsb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="v_89xsb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fastapi" {...props}></Icon>
