<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkttoyb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nkttoyb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flip-vertical-outline" {...props}></Icon>
