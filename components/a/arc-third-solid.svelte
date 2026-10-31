<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o17z0g3wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o17z0g3wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arc-third-solid" {...props}></Icon>
