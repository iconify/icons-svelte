<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0ofj7b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v0ofj7b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:clockalt" {...props}></Icon>
