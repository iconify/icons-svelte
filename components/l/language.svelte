<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk_4ahm4b.css';
import '../../css/f/fvv8vzbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk_4ahm4b wm-k"/><path class="fvv8vzbvy wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:language" {...props}></Icon>
