<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eif-8lxuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eif-8lxuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:park-alt1" {...props}></Icon>
