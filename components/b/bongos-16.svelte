<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd9bq4beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jd9bq4beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:bongos-16" {...props}></Icon>
