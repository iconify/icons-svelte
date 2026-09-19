<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrrqiobds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vrrqiobds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:piano" {...props}></Icon>
