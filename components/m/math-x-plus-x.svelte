<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyaxeyu_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyaxeyu_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-x-plus-x" {...props}></Icon>
