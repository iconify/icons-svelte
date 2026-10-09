<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyr9-qb4r.css';
import '../../css/f/fcdrigb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dyr9-qb4r"/><path class="fcdrigb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crucible-20" {...props}></Icon>
