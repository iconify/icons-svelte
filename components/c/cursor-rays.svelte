<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v--_2jb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="v--_2jb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cursor-rays" {...props}></Icon>
