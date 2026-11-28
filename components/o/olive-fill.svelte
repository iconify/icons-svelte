<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovof3zl8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ovof3zl8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:olive-fill" {...props}></Icon>
