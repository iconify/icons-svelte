<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stifp2bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="stifp2bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:liver-alt-outline-24px" {...props}></Icon>
