<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5hbqvx0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="o5hbqvx0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:plus" {...props}></Icon>
