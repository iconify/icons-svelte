<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5pd71w6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="c5pd71w6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:lock-open" {...props}></Icon>
