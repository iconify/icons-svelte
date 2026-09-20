<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o90uxgbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o90uxgbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:rectangle-split-thirds-remix" {...props}></Icon>
