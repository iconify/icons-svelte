<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-vu94bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-vu94bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:course-filled" {...props}></Icon>
