<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-_ib7i3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-_ib7i3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:archive-box-x-mark" {...props}></Icon>
