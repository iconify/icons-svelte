<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tat7ojpcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tat7ojpcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:crowdin" {...props}></Icon>
