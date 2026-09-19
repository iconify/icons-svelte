<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl3s5wbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bl3s5wbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-control-small" {...props}></Icon>
