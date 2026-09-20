<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvhqw7b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vvhqw7b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:expand-up" {...props}></Icon>
