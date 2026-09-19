<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/namfkl8ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="namfkl8ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:paste-as-text" {...props}></Icon>
