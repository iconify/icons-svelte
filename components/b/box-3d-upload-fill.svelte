<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6g-occ4g.css';
import '../../css/l/luiwpibjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6g-occ4g"/><path class="luiwpibjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-3d-upload-fill" {...props}></Icon>
