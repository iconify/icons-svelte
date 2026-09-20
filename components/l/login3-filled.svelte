<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abqt2_evv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abqt2_evv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:login3-filled" {...props}></Icon>
