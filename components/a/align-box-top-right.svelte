<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daefol3mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="daefol3mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-top-right" {...props}></Icon>
