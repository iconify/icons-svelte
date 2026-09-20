<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_fg-2buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q_fg-2buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:docs" {...props}></Icon>
