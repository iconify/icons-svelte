<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9t9wrb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g9t9wrb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:mail" {...props}></Icon>
