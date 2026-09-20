<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eobcxt-xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eobcxt-xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:armchair-2-outline" {...props}></Icon>
