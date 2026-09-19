<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihkv5i5wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ihkv5i5wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pimcore" {...props}></Icon>
