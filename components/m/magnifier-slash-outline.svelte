<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_sy2m0fq.css';
import '../../css/v/vyk6wnbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_sy2m0fq"/><path clip-rule="evenodd" class="vyk6wnbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-slash-outline" {...props}></Icon>
