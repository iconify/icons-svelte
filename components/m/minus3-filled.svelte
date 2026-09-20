<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myf67vu-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myf67vu-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:minus3-filled" {...props}></Icon>
