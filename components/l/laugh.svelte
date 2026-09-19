<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aziub6dhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aziub6dhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:laugh" {...props}></Icon>
