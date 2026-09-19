<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7s1monoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7s1monoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:jsx-02" {...props}></Icon>
