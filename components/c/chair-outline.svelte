<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1qudoxlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1qudoxlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chair-outline" {...props}></Icon>
