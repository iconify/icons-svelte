<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdof_xbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdof_xbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-empty-02" {...props}></Icon>
