<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b04z-5r7l.css';
import '../../css/h/h848uabup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b04z-5r7l"/><path class="h848uabup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bandage" {...props}></Icon>
