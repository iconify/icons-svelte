<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnvhbrb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qnvhbrb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:canceled-circle" {...props}></Icon>
