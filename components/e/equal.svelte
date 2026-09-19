<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kikwrcevj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kikwrcevj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:equal" {...props}></Icon>
