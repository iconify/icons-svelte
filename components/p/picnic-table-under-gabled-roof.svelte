<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8cjq9bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n8cjq9bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:picnic-table-under-gabled-roof" {...props}></Icon>
