<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3f_7bcue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v3f_7bcue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bag-remix" {...props}></Icon>
