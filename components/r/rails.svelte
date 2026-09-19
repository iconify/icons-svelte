<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of88hrgyb.css';
import '../../css/h/hcquu7bpt.css';
import '../../css/y/ys_j6cbby.css';
import '../../css/b/b99j4mbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of88hrgyb"/><path class="hcquu7bpt"/><path class="ys_j6cbby"/><path class="b99j4mbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:rails" {...props}></Icon>
