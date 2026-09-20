<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtj7l935b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="rtj7l935b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:past" {...props}></Icon>
