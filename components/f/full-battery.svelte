<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr5qf2b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="tr5qf2b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:full-battery" {...props}></Icon>
