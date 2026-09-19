<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt811tlus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qt811tlus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:minus-square" {...props}></Icon>
