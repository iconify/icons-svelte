<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkmxy1dof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qkmxy1dof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:repeat" {...props}></Icon>
