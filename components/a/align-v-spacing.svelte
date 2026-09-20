<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e577qbfcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e577qbfcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:align-v-spacing" {...props}></Icon>
