<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3tp4bcgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3tp4bcgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:like" {...props}></Icon>
