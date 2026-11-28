<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvge9hbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvge9hbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:beer-plus" {...props}></Icon>
