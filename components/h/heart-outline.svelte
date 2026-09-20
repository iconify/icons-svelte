<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss57cos9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ss57cos9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-outline" {...props}></Icon>
