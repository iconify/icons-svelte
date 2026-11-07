<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ugcyjie.css';
import '../../css/a/al80obcvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ugcyjie"/><path clip-rule="evenodd" class="al80obcvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:benzene-ring-outline" {...props}></Icon>
