<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zue1_br6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zue1_br6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:ellipsis-vertical" {...props}></Icon>
