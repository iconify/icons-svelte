<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsth7bq1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":800};
const content = `<path class="hsth7bq1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:cup" {...props}></Icon>
