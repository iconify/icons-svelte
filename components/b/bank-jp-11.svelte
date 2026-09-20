<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haf8sabek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="haf8sabek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bank-jp-11" {...props}></Icon>
