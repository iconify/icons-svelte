<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm6j0-c1z.css';
import '../../css/s/s9jco_ufp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm6j0-c1z"/><path clip-rule="evenodd" class="s9jco_ufp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:instagram-solid" {...props}></Icon>
