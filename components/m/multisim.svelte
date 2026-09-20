<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dho9ptbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dho9ptbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:multisim" {...props}></Icon>
