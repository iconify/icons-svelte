<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpk0tl1ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpk0tl1ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:layout-plus" {...props}></Icon>
