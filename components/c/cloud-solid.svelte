<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c979wo3lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c979wo3lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-solid" {...props}></Icon>
