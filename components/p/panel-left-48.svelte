<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3q6uacna.css';
import '../../css/t/ta7bnee7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v3q6uacna"/><path class="ta7bnee7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-left-48" {...props}></Icon>
