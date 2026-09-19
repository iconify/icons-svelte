<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvowzcblg.css';
import '../../css/l/ljexf9bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer kvowzcblg"/><path class="duoicon-primary-layer ljexf9bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:clapperboard" {...props}></Icon>
