<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrdvcwidb.css';
import '../../css/g/gjmvk5b4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path clip-rule="evenodd" class="gjmvk5b4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hashtag-circle-bold-duotone" {...props}></Icon>
