<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vagjwfb3n.css';
import '../../css/b/ba21eebdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vagjwfb3n"/><path class="ba21eebdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:airplay-filled" {...props}></Icon>
