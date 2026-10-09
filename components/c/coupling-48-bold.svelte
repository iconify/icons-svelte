<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isqhvabpe.css';
import '../../css/a/a13mabcgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="isqhvabpe"/><path class="a13mabcgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coupling-48-bold" {...props}></Icon>
