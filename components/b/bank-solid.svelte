<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqglnrb0z.css';
import '../../css/s/s6o6votsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wqglnrb0z"/><path clip-rule="evenodd" class="s6o6votsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bank-solid" {...props}></Icon>
