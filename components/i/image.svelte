<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhket41bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhket41bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:image" {...props}></Icon>
