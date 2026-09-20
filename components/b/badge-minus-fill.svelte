<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6sfflbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6sfflbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:badge-minus-fill" {...props}></Icon>
