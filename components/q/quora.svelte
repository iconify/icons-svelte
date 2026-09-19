<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai5_8yjej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="ai5_8yjej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:quora" {...props}></Icon>
