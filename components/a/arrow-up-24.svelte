<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq64mymnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq64mymnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:arrow-up-24" {...props}></Icon>
