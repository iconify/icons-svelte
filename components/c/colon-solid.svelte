<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw46at8gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw46at8gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:colon-solid" {...props}></Icon>
