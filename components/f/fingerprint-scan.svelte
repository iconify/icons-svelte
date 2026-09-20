<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a65wbby8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="a65wbby8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:fingerprint-scan" {...props}></Icon>
