<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c88et_bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c88et_bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-up-left-circle-fill" {...props}></Icon>
