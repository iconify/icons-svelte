<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z64uonb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z64uonb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:praying-hand-remix" {...props}></Icon>
