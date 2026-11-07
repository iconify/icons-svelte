<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_712477j.css';
import '../../css/b/bs6xgtf0q.css';
import '../../css/w/w_p0ksbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_712477j"/><path class="bs6xgtf0q"/><path class="w_p0ksbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:headphones-square-bold-duotone" {...props}></Icon>
