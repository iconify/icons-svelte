<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg5aw4bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg5aw4bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:arrow-down-circle" {...props}></Icon>
