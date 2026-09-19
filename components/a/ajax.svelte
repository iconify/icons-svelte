<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnnnaqbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":767,"height":1024};
const content = `<path class="gnnnaqbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ajax" {...props}></Icon>
