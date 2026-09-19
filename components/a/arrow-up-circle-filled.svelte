<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5yuqmboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5yuqmboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-circle-filled" {...props}></Icon>
