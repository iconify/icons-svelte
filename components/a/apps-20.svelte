<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi9ifmbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vi9ifmbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:apps-20" {...props}></Icon>
