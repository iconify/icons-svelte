<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afh00gbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afh00gbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:polygon-zkevm" {...props}></Icon>
