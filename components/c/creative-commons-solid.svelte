<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krbyhebzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krbyhebzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:creative-commons-solid" {...props}></Icon>
