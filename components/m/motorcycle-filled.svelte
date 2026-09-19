<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2ap08bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2ap08bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:motorcycle-filled" {...props}></Icon>
