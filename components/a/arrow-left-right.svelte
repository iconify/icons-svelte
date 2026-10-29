<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izjg96b3x.css';
import '../../css/v/vvtazx08m.css';
import '../../css/d/dx5io4b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izjg96b3x"/><path class="vvtazx08m"/><path class="dx5io4b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:arrow-left-right" {...props}></Icon>
