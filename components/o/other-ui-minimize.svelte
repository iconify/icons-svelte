<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r79vzpj4a.css';
import '../../css/b/bijcxwbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r79vzpj4a"/><path class="bijcxwbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-minimize" {...props}></Icon>
