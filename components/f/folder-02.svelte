<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwcynvbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwcynvbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-02" {...props}></Icon>
