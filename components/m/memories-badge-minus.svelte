<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c61345ufy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="c61345ufy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:memories-badge-minus" {...props}></Icon>
