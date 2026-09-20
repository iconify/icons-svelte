<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odwa7xv4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odwa7xv4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:panel-bottom" {...props}></Icon>
