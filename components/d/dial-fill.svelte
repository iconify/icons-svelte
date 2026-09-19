<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isvqbrb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="isvqbrb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:dial-fill" {...props}></Icon>
