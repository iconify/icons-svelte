<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbxewab1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbxewab1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-number-8-filled" {...props}></Icon>
