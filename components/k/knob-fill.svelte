<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv9bp2bij.css';
import '../../css/g/g-trd5b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vv9bp2bij"/><path class="g-trd5b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:knob-fill" {...props}></Icon>
