<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-rswabiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":392,"height":448};
const content = `<path class="c-rswabiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:justice" {...props}></Icon>
