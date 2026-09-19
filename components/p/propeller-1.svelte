<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kht4czj5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="kht4czj5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:propeller-1" {...props}></Icon>
