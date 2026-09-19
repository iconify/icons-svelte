<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo01anvpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="zo01anvpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-up-right-box" {...props}></Icon>
