<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg1la2bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qg1la2bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-fast-forward-2-remix" {...props}></Icon>
