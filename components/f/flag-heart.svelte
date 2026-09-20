<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld5bepe6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld5bepe6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-heart" {...props}></Icon>
