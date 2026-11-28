<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbblyu8os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbblyu8os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-write-solid" {...props}></Icon>
