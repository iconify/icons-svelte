<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkcm9o7dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkcm9o7dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:hair-dryer" {...props}></Icon>
