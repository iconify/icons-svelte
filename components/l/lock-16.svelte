<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt58u3bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pt58u3bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:lock-16" {...props}></Icon>
