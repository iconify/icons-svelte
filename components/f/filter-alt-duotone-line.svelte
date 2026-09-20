<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7ggnqb5n.css';
import '../../css/n/nuxe1q7gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k7ggnqb5n"/><path class="nuxe1q7gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:filter-alt-duotone-line" {...props}></Icon>
