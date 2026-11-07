<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgd8bzbml.css';
import '../../css/g/g5_-wqbhf.css';
import '../../css/s/sn15dubbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgd8bzbml"/><path class="g5_-wqbhf"/><path class="sn15dubbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-send-bold-duotone" {...props}></Icon>
