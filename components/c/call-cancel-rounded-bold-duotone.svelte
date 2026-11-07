<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is_2cgerd.css';
import '../../css/s/s02o69bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="is_2cgerd"/><path class="s02o69bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-cancel-rounded-bold-duotone" {...props}></Icon>
