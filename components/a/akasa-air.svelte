<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a206w9bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a206w9bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:akasa-air" {...props}></Icon>
