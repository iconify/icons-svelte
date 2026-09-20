<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl5erow2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl5erow2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-left-close-sharp" {...props}></Icon>
