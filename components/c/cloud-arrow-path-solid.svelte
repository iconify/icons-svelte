<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpob04b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpob04b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-arrow-path-solid" {...props}></Icon>
