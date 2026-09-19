<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4jgbu-ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4jgbu-ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:loading-02" {...props}></Icon>
