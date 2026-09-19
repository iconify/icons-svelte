<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvwzhz6sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tvwzhz6sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:mail-open" {...props}></Icon>
