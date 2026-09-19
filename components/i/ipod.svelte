<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrvkwrb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="zrvkwrb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:ipod" {...props}></Icon>
