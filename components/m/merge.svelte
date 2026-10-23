<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls8ogociq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls8ogociq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:merge" {...props}></Icon>
