<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0ios115f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0ios115f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:help" {...props}></Icon>
