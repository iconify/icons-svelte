<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1gs-gb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1gs-gb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:key-round-solid" {...props}></Icon>
