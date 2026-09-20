<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy7nfem9n.css';
import '../../css/w/wgkp86hhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy7nfem9n"/><path class="wgkp86hhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kujira" {...props}></Icon>
