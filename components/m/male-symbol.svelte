<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dusfo0bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="dusfo0bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:male-symbol" {...props}></Icon>
