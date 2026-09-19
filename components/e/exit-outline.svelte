<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1a5g-bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1a5g-bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:exit-outline" {...props}></Icon>
