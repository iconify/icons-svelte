<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm84pkbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jm84pkbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-long-left-solid" {...props}></Icon>
