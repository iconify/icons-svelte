<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj7bijbti.css';
import '../../css/j/jsfpydcpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj7bijbti"/><path class="jsfpydcpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:medium-square" {...props}></Icon>
