<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh23mfb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh23mfb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder" {...props}></Icon>
