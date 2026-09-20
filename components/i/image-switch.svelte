<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm5zddb2t.css';
import '../../css/v/vcti67wgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm5zddb2t"/><path class="vcti67wgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-switch" {...props}></Icon>
