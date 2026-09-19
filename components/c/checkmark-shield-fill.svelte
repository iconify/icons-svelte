<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa-4lbc2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="aa-4lbc2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:checkmark-shield-fill" {...props}></Icon>
