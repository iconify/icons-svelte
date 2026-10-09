<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbybcrbbp.css';
import '../../css/o/olr0j3b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bbybcrbbp"/><path class="olr0j3b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alert-20" {...props}></Icon>
