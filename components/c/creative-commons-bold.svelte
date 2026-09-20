<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmji0zbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kmji0zbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:creative-commons-bold" {...props}></Icon>
