<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-uzlabum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-uzlabum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:national-rail" {...props}></Icon>
