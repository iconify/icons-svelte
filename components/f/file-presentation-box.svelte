<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grw0rhcqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grw0rhcqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-presentation-box" {...props}></Icon>
