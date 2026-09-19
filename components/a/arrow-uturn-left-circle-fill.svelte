<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsf6grz5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lsf6grz5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-uturn-left-circle-fill" {...props}></Icon>
