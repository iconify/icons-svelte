<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n970xwb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n970xwb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:musical-note-solid" {...props}></Icon>
