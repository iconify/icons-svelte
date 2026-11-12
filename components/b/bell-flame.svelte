<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbtvdn1tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbtvdn1tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-flame" {...props}></Icon>
