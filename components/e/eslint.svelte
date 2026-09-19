<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2govyb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u2govyb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:eslint" {...props}></Icon>
