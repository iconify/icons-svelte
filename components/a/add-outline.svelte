<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6crs6blw.css';
import '../../css/b/buewkbcgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6crs6blw"/><path clip-rule="evenodd" class="buewkbcgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:add-outline" {...props}></Icon>
