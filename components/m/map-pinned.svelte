<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is090zbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="is090zbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:map-pinned" {...props}></Icon>
