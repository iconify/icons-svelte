<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9jlb0bcj.css';
import '../../css/t/t-558ne9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v9jlb0bcj"/><path class="t-558ne9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desert-48" {...props}></Icon>
