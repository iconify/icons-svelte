<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewn1ke3br.css';
import '../../css/x/xxdenrb3z.css';
import '../../css/l/lqnnr9bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewn1ke3br"/><path class="xxdenrb3z"/><path class="lqnnr9bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:film-20" {...props}></Icon>
