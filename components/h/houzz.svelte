<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8yhhqb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":577.176,"height":1000};
const content = `<path class="m8yhhqb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:houzz" {...props}></Icon>
