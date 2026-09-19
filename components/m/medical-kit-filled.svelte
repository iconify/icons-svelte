<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksgk5qbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksgk5qbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:medical-kit-filled" {...props}></Icon>
