<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smc5l5zng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smc5l5zng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:down-two-headed-fill" {...props}></Icon>
