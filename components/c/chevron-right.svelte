<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9pep4b0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="m9pep4b0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-right" {...props}></Icon>
