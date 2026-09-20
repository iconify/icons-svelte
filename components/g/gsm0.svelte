<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sajs9zlog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sajs9zlog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gsm0" {...props}></Icon>
