<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2wul1yco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2wul1yco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-edit-filled" {...props}></Icon>
