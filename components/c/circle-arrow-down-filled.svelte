<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ervr_zbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ervr_zbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrow-down-filled" {...props}></Icon>
