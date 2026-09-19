<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p47787cdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p47787cdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:bounce" {...props}></Icon>
