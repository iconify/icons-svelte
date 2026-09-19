<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ori4jfh0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ori4jfh0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bacteria-filled" {...props}></Icon>
