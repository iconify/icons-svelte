<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka8nnc9vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ka8nnc9vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:expand" {...props}></Icon>
