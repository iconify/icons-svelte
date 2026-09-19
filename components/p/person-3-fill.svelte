<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkoonwrcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="bkoonwrcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-3-fill" {...props}></Icon>
