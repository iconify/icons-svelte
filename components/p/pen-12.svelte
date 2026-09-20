<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzvzhujzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="yzvzhujzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:pen-12" {...props}></Icon>
