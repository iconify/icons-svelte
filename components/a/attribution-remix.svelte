<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu0dt5bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wu0dt5bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:attribution-remix" {...props}></Icon>
