<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbnmd3bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kbnmd3bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hierarchy-2-remix" {...props}></Icon>
