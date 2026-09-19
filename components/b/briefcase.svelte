<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9uq9xp4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d9uq9xp4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:briefcase" {...props}></Icon>
