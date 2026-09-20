<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbcwdowdw.css';
import '../../css/c/crhlcxbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fbcwdowdw"/><path class="crhlcxbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:infinity-bold-duotone" {...props}></Icon>
