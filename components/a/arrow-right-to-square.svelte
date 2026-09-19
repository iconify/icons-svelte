<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdln7bb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qdln7bb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-right-to-square" {...props}></Icon>
