<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3-vpb73p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3-vpb73p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pharagraphspacing" {...props}></Icon>
