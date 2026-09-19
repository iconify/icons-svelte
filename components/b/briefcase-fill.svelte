<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4f9lhb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="z4f9lhb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:briefcase-fill" {...props}></Icon>
