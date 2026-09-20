<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg8ti8thn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg8ti8thn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-left-thick" {...props}></Icon>
