<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3r4zzb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3r4zzb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:dollar-line" {...props}></Icon>
