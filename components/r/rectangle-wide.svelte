<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d703htbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d703htbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rectangle-wide" {...props}></Icon>
