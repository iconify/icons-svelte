<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt4-40r2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bt4-40r2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:backward-step" {...props}></Icon>
