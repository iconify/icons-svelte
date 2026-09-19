<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epec9q7br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epec9q7br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:compress-v" {...props}></Icon>
