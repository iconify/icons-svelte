<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqtzitbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqtzitbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-to-bottom-filled" {...props}></Icon>
