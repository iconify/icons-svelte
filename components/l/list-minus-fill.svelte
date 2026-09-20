<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdc9n4l0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdc9n4l0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-minus-fill" {...props}></Icon>
