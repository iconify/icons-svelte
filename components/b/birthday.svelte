<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6vjh8byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="i6vjh8byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:birthday" {...props}></Icon>
