<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c88vd2bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c88vd2bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chevron-left-square-fill" {...props}></Icon>
