<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx3zlefwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx3zlefwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-up-left-square-fill" {...props}></Icon>
