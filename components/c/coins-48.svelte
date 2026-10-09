<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqf7b7ozo.css';
import '../../css/x/xa5rde75k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wqf7b7ozo"/><path class="xa5rde75k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coins-48" {...props}></Icon>
