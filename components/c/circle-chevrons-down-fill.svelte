<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktpdosbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktpdosbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevrons-down-fill" {...props}></Icon>
