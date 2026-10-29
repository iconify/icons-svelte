<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz4027bss.css';
import '../../css/h/hdke9bc-g.css';
import '../../css/p/pvl81kbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz4027bss wm-a"/><path class="hdke9bc-g wm-k"/><path class="pvl81kbjy wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:headphones" {...props}></Icon>
