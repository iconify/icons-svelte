<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqur9absj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqur9absj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:filter-1-filled" {...props}></Icon>
