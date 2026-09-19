<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohqz0n9ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ohqz0n9ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-right-circle" {...props}></Icon>
