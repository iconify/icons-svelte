<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh5gjdb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh5gjdb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:honor" {...props}></Icon>
