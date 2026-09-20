<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs_gzj8dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs_gzj8dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:release-notes-fill" {...props}></Icon>
