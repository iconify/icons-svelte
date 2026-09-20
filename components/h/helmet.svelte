<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7tpezbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="v7tpezbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:helmet" {...props}></Icon>
