<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9xki7bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9xki7bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:folder-check-fill" {...props}></Icon>
