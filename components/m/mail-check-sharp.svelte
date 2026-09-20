<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn958gbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn958gbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mail-check-sharp" {...props}></Icon>
