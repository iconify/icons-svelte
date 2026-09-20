<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gko5h7otm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gko5h7otm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:affinity-publiser-logo" {...props}></Icon>
