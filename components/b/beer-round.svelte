<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6li8ib6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6li8ib6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:beer-round" {...props}></Icon>
