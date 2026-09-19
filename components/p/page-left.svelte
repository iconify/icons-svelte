<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1fd6bbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="a1fd6bbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:page-left" {...props}></Icon>
