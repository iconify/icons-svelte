<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsobnkbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsobnkbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-open-sharp-duotone" {...props}></Icon>
