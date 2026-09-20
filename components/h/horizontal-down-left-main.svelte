<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifde2vb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifde2vb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:horizontal-down-left-main" {...props}></Icon>
