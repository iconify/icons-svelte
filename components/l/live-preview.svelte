<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9cykllwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i9cykllwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:live-preview" {...props}></Icon>
