<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py86dxbyc.css';
import '../../css/k/km474465y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py86dxbyc"/><path clip-rule="evenodd" class="km474465y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-plus" {...props}></Icon>
