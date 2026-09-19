<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7i9stpdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u7i9stpdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:phone-20-solid" {...props}></Icon>
