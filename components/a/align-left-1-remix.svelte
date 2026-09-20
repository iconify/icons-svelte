<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eud5tvbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eud5tvbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:align-left-1-remix" {...props}></Icon>
