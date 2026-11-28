<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax-e-ryoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax-e-ryoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-document-solid" {...props}></Icon>
