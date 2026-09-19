<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3xtccvpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="m3xtccvpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-circle-fill" {...props}></Icon>
