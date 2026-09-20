<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-l9itbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l-l9itbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:insert-top-left-remix" {...props}></Icon>
