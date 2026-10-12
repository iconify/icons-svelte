<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej-7496ya.css';
import '../../css/b/bbhbk04qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ej-7496ya"/><path class="bbhbk04qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hurricane-20" {...props}></Icon>
