<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0xnzza0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q0xnzza0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:building-alt-3-fill" {...props}></Icon>
