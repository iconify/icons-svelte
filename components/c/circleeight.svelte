<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6mjfobis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="t6mjfobis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleeight" {...props}></Icon>
