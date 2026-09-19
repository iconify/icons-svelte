<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj58hmgby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oj58hmgby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:pre" {...props}></Icon>
