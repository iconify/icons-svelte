<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv5pv62hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv5pv62hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:authy" {...props}></Icon>
