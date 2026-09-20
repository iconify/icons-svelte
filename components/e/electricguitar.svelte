<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y47ihgbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="y47ihgbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:electricguitar" {...props}></Icon>
