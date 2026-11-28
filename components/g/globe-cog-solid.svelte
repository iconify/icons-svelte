<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v460hd2nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v460hd2nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:globe-cog-solid" {...props}></Icon>
