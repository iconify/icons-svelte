<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s917mrb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s917mrb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:g" {...props}></Icon>
