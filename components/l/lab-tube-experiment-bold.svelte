<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez79efb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez79efb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:lab-tube-experiment-bold" {...props}></Icon>
