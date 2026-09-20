<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-log0e6r.css';
import '../../css/e/e4me81bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-log0e6r"/><path clip-rule="evenodd" class="e4me81bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:globe-stand" {...props}></Icon>
