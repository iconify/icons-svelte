<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc-b-cbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc-b-cbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:caret-up" {...props}></Icon>
