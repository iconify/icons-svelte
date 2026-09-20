<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh2zh0bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gh2zh0bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:list-down2" {...props}></Icon>
