<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdoiz26ay.css';
import '../../css/t/tc6em5bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdoiz26ay"/><path class="tc6em5bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mdt" {...props}></Icon>
