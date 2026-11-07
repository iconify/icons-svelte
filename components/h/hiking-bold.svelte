<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxi8hkb5i.css';
import '../../css/h/hvxzctpfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxi8hkb5i"/><path clip-rule="evenodd" class="hvxzctpfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hiking-bold" {...props}></Icon>
