<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcce5mspk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcce5mspk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:criminal-fill" {...props}></Icon>
