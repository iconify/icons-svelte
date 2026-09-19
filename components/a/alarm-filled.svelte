<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whof3db5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whof3db5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-filled" {...props}></Icon>
