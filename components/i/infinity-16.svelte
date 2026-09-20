<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-xzx7bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p-xzx7bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:infinity-16" {...props}></Icon>
