<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbc6i7byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbc6i7byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:folder-key" {...props}></Icon>
