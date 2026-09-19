<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rehoz_bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<path class="rehoz_bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:code" {...props}></Icon>
