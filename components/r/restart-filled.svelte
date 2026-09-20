<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qea01pbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qea01pbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:restart-filled" {...props}></Icon>
