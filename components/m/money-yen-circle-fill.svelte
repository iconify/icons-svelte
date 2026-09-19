<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-tzf4blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d-tzf4blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:money-yen-circle-fill" {...props}></Icon>
