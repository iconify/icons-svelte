<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykinii4jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykinii4jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:numbers" {...props}></Icon>
