<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoi0s-bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoi0s-bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cypherock" {...props}></Icon>
