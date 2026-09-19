<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv1hvdbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fv1hvdbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:column-dependency" {...props}></Icon>
