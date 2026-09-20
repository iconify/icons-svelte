<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge_mu3bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ge_mu3bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:folder-check" {...props}></Icon>
