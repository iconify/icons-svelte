<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-o_25boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o-o_25boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:paintbrush-solid" {...props}></Icon>
