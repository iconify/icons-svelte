<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kai_8tblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kai_8tblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-slider" {...props}></Icon>
