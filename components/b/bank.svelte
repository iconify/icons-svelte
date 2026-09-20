<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzk-r7a0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jzk-r7a0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:bank" {...props}></Icon>
