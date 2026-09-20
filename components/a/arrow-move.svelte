<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvjs9ibqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvjs9ibqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-move" {...props}></Icon>
