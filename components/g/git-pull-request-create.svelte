<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km6do4blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km6do4blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:git-pull-request-create" {...props}></Icon>
