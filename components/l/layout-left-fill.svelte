<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1ja_vads.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1ja_vads"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:layout-left-fill" {...props}></Icon>
