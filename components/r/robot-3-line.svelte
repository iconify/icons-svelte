<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf6irmbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf6irmbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:robot-3-line" {...props}></Icon>
