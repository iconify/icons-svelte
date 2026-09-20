<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hljqksfof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hljqksfof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:bring-forward" {...props}></Icon>
