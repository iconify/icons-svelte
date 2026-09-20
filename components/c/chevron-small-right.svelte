<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4ob6t.css';
import '../../css/s/so-from-10.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4ob6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-small-right" {...props}></Icon>
