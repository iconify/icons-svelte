<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf2qmgbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xf2qmgbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:dollar-solid" {...props}></Icon>
