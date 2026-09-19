<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc8_0qt7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc8_0qt7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:long-text-outline" {...props}></Icon>
