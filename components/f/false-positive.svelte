<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7-mkdg7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l7-mkdg7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:false-positive" {...props}></Icon>
