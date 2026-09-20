<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2gx3t1mk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o2gx3t1mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:infinite-filled" {...props}></Icon>
