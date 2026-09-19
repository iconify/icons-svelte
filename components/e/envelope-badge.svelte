<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w61psqb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w61psqb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:envelope-badge" {...props}></Icon>
