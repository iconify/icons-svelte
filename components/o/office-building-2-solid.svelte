<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6c40bb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6c40bb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:office-building-2-solid" {...props}></Icon>
