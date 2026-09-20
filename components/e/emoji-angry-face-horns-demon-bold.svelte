<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5b7hjb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5b7hjb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:emoji-angry-face-horns-demon-bold" {...props}></Icon>
