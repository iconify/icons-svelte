<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cth7kpfnp.css';
import '../../css/a/azpullbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cth7kpfnp"/><path class="azpullbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bolt-bold-duotone" {...props}></Icon>
