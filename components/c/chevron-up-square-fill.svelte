<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4jcqrw0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="s4jcqrw0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-up-square-fill" {...props}></Icon>
