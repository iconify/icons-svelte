<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgd8bzbml.css';
import '../../css/r/rrc0fzxvj.css';
import '../../css/s/sn15dubbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgd8bzbml"/><path class="rrc0fzxvj"/><path class="sn15dubbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-download-bold-duotone" {...props}></Icon>
