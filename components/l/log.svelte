<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd5xcgt6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pd5xcgt6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:log" {...props}></Icon>
