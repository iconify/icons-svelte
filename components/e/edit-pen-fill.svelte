<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh4hvxbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh4hvxbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:edit-pen-fill" {...props}></Icon>
