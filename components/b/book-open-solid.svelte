<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jif2-ff-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jif2-ff-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:book-open-solid" {...props}></Icon>
