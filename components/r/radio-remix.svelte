<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slgty_bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="slgty_bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:radio-remix" {...props}></Icon>
