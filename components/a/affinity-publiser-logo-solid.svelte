<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxg7tg66d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gxg7tg66d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:affinity-publiser-logo-solid" {...props}></Icon>
