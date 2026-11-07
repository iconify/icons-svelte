<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu18-_bab.css';
import '../../css/l/lg9shfpyb.css';
import '../../css/a/acdg-bc6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu18-_bab"/><path class="lg9shfpyb"/><path clip-rule="evenodd" class="acdg-bc6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:face-scan-square-outline" {...props}></Icon>
