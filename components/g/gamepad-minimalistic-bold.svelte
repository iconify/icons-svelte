<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb74pc30f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qb74pc30f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gamepad-minimalistic-bold" {...props}></Icon>
