<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztsas3gev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ztsas3gev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:address-book-solid" {...props}></Icon>
