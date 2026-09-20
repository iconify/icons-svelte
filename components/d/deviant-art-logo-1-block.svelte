<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8r1e1_by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g8r1e1_by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:deviant-art-logo-1-block" {...props}></Icon>
