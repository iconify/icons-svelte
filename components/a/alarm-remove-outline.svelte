<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxjzssbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lxjzssbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alarm-remove-outline" {...props}></Icon>
