<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu6-2cbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu6-2cbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:european-union" {...props}></Icon>
