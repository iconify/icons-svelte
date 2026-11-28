<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blbxorbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blbxorbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:baseball" {...props}></Icon>
