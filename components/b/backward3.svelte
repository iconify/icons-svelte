<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-9rg3bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-9rg3bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:backward3" {...props}></Icon>
