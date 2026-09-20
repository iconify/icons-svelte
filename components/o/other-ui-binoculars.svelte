<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7dlj0bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u7dlj0bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-binoculars" {...props}></Icon>
