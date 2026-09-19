<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0bz8sb9m.css';
import '../../css/r/rs6irjb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0bz8sb9m"/><path class="rs6irjb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:check-circle" {...props}></Icon>
