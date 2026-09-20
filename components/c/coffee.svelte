<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enh0vvopo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enh0vvopo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:coffee" {...props}></Icon>
