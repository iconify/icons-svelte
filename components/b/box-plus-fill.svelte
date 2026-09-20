<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plzwab3-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plzwab3-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-plus-fill" {...props}></Icon>
