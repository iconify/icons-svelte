<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm995dbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jm995dbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:flag" {...props}></Icon>
