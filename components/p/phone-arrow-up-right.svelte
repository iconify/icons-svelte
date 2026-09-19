<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5m50g79g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5m50g79g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:phone-arrow-up-right" {...props}></Icon>
