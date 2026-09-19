<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9028ebbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="y9028ebbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:goforward-plus" {...props}></Icon>
