<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu-hzwb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu-hzwb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-cross-filled" {...props}></Icon>
