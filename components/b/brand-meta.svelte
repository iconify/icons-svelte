<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obh3ssbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obh3ssbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-meta" {...props}></Icon>
