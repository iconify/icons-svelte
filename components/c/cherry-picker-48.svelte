<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvqwjdbok.css';
import '../../css/f/fb99aacni.css';
import '../../css/c/c-5-uyb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nvqwjdbok"/><path class="fb99aacni"/><path class="c-5-uyb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cherry-picker-48" {...props}></Icon>
