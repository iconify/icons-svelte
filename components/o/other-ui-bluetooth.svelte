<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cukznhofj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cukznhofj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-bluetooth" {...props}></Icon>
