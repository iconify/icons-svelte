<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsq5iorbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lsq5iorbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:gift" {...props}></Icon>
