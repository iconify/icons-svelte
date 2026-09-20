<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agas_nbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agas_nbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:qrl" {...props}></Icon>
