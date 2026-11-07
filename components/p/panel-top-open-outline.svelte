<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exa2uu4rz.css';
import '../../css/u/ur3_zfbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exa2uu4rz"/><path clip-rule="evenodd" class="ur3_zfbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-top-open-outline" {...props}></Icon>
