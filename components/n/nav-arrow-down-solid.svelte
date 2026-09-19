<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4a6h4vee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u4a6h4vee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:nav-arrow-down-solid" {...props}></Icon>
