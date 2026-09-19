<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdvbt-kba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdvbt-kba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:key" {...props}></Icon>
