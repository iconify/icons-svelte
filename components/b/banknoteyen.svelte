<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eebag5dgs.css';
import '../../css/v/vlmk0rb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eebag5dgs"/><path class="vlmk0rb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:banknoteyen" {...props}></Icon>
