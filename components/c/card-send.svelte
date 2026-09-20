<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxts2hb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yxts2hb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:card-send" {...props}></Icon>
