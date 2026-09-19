<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk_2qoknp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kk_2qoknp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:archive-box-arrow-down" {...props}></Icon>
