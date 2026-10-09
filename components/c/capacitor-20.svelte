<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_wwqhb6k.css';
import '../../css/s/sd5b7gblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f_wwqhb6k"/><path class="sd5b7gblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:capacitor-20" {...props}></Icon>
