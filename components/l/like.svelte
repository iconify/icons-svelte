<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrbu_pbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrbu_pbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:like" {...props}></Icon>
