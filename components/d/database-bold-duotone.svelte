<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj705hhir.css';
import '../../css/i/ios08bb7p.css';
import '../../css/x/xi4-07bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj705hhir"/><path class="ios08bb7p"/><path class="xi4-07bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:database-bold-duotone" {...props}></Icon>
