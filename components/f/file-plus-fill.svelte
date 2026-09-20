<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as74db1rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as74db1rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:file-plus-fill" {...props}></Icon>
