<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtor0hbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtor0hbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:contact-search" {...props}></Icon>
