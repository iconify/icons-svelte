<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5a7kgjlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5a7kgjlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:photo-album-fill" {...props}></Icon>
