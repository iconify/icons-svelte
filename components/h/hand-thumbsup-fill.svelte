<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnu1-rb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vnu1-rb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hand-thumbsup-fill" {...props}></Icon>
