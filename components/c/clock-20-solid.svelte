<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzxmglb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="uzxmglb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:clock-20-solid" {...props}></Icon>
