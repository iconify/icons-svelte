<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m903izb2c.css';
import '../../css/a/agkkf9bgs.css';
import '../../css/h/huqxzg8tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m903izb2c wm-a"/><path class="agkkf9bgs wm-k"/><path class="huqxzg8tr wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:plug" {...props}></Icon>
