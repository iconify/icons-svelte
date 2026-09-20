<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m32ua02qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m32ua02qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chevron-left" {...props}></Icon>
