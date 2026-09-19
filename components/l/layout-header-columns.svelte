<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk6b_0bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zk6b_0bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:layout-header-columns" {...props}></Icon>
