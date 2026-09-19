<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o13g0ubbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="o13g0ubbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:frown" {...props}></Icon>
