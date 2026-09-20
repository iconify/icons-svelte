<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhy5ambjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qhy5ambjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:database-server-2-remix" {...props}></Icon>
