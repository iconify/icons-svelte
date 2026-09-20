<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od9an0bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="od9an0bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:crown-star-filled" {...props}></Icon>
