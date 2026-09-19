<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6gvj_2af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6gvj_2af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-left-lg" {...props}></Icon>
