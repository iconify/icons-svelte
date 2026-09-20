<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bie8y9lpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bie8y9lpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:information-slab-symbol" {...props}></Icon>
