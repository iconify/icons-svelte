<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dulco3bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dulco3bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:moon-circle" {...props}></Icon>
