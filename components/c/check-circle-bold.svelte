<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svxrt0bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svxrt0bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:check-circle-bold" {...props}></Icon>
