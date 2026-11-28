<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx-snub-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx-snub-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chalkboard-edit" {...props}></Icon>
