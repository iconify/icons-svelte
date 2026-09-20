<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f658hbdqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f658hbdqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:outdent" {...props}></Icon>
