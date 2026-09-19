<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d85qszb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d85qszb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:baby-male-0203m-negative" {...props}></Icon>
