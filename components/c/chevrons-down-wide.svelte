<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poc80mb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="poc80mb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:chevrons-down-wide" {...props}></Icon>
