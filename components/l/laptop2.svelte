<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypo4sbb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ypo4sbb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:laptop2" {...props}></Icon>
