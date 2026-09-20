<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i12vpz_eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i12vpz_eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:folder-2" {...props}></Icon>
