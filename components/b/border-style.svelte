<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujx4dsesw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ujx4dsesw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:border-style" {...props}></Icon>
