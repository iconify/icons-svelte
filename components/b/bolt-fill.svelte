<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg_ed7b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg_ed7b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:bolt-fill" {...props}></Icon>
