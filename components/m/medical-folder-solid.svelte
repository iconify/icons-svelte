<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qghu-3aqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qghu-3aqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:medical-folder-solid" {...props}></Icon>
