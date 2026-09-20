<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4es6rmzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a4es6rmzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-top-right-with-plus" {...props}></Icon>
