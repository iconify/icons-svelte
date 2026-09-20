<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iufw5acos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iufw5acos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-down" {...props}></Icon>
