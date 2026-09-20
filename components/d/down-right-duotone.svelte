<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5s2c3bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5s2c3bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:down-right-duotone" {...props}></Icon>
