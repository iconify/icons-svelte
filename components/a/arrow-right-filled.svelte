<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdif1-9fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kdif1-9fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:arrow-right-filled" {...props}></Icon>
