<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odz7kjb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="odz7kjb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:caret-left" {...props}></Icon>
