<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya4sl-brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya4sl-brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:perfume-bottle-filled" {...props}></Icon>
