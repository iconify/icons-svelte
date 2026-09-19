<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osla50jfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osla50jfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:lock-open" {...props}></Icon>
