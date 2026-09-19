<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7u5d87up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="b7u5d87up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:flag" {...props}></Icon>
