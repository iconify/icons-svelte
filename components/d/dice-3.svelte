<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-kyxtbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-kyxtbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:dice-3" {...props}></Icon>
