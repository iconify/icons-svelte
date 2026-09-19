<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezq_5gb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ezq_5gb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:insert-table" {...props}></Icon>
