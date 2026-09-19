<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4-zn3bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":737,"height":729};
const content = `<path class="n4-zn3bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:internetexplorer" {...props}></Icon>
