<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr0qihbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sr0qihbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:raised-hand-small" {...props}></Icon>
