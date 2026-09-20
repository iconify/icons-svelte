<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1rxlt9qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1rxlt9qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:gender-demigirl" {...props}></Icon>
