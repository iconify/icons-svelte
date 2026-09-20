<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we660hbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we660hbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-word-2-line" {...props}></Icon>
