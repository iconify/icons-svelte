<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y892mo3mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y892mo3mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-pyramid-sharp" {...props}></Icon>
