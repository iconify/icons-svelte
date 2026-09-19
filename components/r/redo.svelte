<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8u6r351b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="v8u6r351b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:redo" {...props}></Icon>
