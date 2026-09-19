<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpytocctq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gpytocctq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-paperclip" {...props}></Icon>
