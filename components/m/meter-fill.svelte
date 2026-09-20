<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v36pdtiyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v36pdtiyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:meter-fill" {...props}></Icon>
