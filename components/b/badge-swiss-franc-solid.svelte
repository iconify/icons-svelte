<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y25geurdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y25geurdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-swiss-franc-solid" {...props}></Icon>
