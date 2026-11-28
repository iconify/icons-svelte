<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-pb3-s-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-pb3-s-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-input-solid" {...props}></Icon>
