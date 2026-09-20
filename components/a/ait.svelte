<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-yalvqiy.css';
import '../../css/k/kj3mfibmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-yalvqiy"/><path class="kj3mfibmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ait" {...props}></Icon>
