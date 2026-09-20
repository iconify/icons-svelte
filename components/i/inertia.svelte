<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by662ib7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by662ib7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:inertia" {...props}></Icon>
