<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a59jnubsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a59jnubsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:information-solid" {...props}></Icon>
