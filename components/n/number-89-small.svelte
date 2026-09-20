<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5k8jqkpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5k8jqkpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-89-small" {...props}></Icon>
