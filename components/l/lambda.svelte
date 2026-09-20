<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgx48ktia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgx48ktia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lambda" {...props}></Icon>
