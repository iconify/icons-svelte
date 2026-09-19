<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_2s79bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="q_2s79bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:envelope-fill" {...props}></Icon>
