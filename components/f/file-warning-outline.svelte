<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5sw_jabn.css';
import '../../css/y/yrd2shbbf.css';
import '../../css/d/d25mwn3tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5sw_jabn"/><path class="yrd2shbbf"/><path clip-rule="evenodd" class="d25mwn3tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-warning-outline" {...props}></Icon>
