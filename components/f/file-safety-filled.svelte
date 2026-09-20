<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7kb0dbiu.css';
import '../../css/o/o5jloubyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7kb0dbiu"/><path class="o5jloubyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-safety-filled" {...props}></Icon>
