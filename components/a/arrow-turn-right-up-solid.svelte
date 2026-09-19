<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcwmwoozx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bcwmwoozx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-right-up-solid" {...props}></Icon>
