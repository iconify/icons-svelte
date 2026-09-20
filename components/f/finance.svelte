<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_hmpwg1c.css';
import '../../css/e/ej-f8xcot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_hmpwg1c"/><path class="ej-f8xcot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:finance" {...props}></Icon>
