<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpj9vf5jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wpj9vf5jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blister-pills-round-x16-24px" {...props}></Icon>
