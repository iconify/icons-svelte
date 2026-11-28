<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djmxe_n-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djmxe_n-i primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:outdent-duotone" {...props}></Icon>
