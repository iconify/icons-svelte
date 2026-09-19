<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agklg4i-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="agklg4i-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:forward-end-fill" {...props}></Icon>
