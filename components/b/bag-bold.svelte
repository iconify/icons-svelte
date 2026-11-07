<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6hm4nbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6hm4nbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-bold" {...props}></Icon>
