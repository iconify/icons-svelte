<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7kopvl8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7kopvl8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:comment-text" {...props}></Icon>
