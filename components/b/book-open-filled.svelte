<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7p_f2brl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7p_f2brl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:book-open-filled" {...props}></Icon>
