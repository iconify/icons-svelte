<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwkw435-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zwkw435-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:doc-expand" {...props}></Icon>
