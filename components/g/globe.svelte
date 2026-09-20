<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h62bnzbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h62bnzbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:globe" {...props}></Icon>
