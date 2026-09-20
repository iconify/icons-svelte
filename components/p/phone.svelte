<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw-o6fboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="kw-o6fboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:phone" {...props}></Icon>
