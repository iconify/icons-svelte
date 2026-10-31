<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju7hpi_7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju7hpi_7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folders-fill-round" {...props}></Icon>
