<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6dn16dyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="b6dn16dyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:remove-format" {...props}></Icon>
