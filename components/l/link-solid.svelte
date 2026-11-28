<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaf20sbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaf20sbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:link-solid" {...props}></Icon>
