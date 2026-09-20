<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w56j2g42u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="w56j2g42u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:maintenance" {...props}></Icon>
