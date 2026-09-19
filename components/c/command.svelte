<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icwqtvx6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="icwqtvx6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:command" {...props}></Icon>
