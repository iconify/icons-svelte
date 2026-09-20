<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0a6y8b1l.css';
import '../../css/u/u407k86qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p0a6y8b1l"/><path class="u407k86qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:briefcases-fill" {...props}></Icon>
