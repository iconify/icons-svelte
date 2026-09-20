<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmf4z0u-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmf4z0u-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-return-sharp" {...props}></Icon>
