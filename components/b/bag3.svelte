<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmyu4uhbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gmyu4uhbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag3" {...props}></Icon>
