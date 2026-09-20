<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b13zlmb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b13zlmb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:component-grid-filled" {...props}></Icon>
