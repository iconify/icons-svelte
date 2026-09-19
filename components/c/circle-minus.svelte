<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3tph2byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3tph2byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circle-minus" {...props}></Icon>
