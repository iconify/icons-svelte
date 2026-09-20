<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm_umbc-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pm_umbc-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ball-solid" {...props}></Icon>
