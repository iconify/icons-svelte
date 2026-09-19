<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x055icb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x055icb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:logo-facebook" {...props}></Icon>
