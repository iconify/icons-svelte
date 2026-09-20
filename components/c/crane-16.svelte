<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy6bdibix.css';
import '../../css/g/gvxfo6vqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hy6bdibix"/><path clip-rule="evenodd" class="gvxfo6vqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:crane-16" {...props}></Icon>
