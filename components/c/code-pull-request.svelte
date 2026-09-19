<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7fxu2b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n7fxu2b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:code-pull-request" {...props}></Icon>
