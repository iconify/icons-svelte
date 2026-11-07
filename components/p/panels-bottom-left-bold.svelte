<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntwgq1b2y.css';
import '../../css/y/yib8xibaw.css';
import '../../css/w/wrbn_p02x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntwgq1b2y"/><path class="yib8xibaw"/><path clip-rule="evenodd" class="wrbn_p02x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-bottom-left-bold" {...props}></Icon>
