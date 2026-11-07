<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayqtpboig.css';
import '../../css/v/vhfpguceu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ayqtpboig"/><path class="vhfpguceu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-bold-duotone" {...props}></Icon>
