<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prhz_2bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prhz_2bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:document" {...props}></Icon>
