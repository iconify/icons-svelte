<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grvocubmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="grvocubmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:propeller-2" {...props}></Icon>
