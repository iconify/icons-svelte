<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k20krjj8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="k20krjj8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hanger" {...props}></Icon>
