<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv32cqbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv32cqbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ghost-solid" {...props}></Icon>
