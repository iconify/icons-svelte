<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phur5pbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phur5pbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bolt-circle" {...props}></Icon>
