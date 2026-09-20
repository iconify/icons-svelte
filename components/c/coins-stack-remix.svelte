<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkuyh1bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bkuyh1bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:coins-stack-remix" {...props}></Icon>
