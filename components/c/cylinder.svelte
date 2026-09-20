<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh5dbu6ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh5dbu6ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:cylinder" {...props}></Icon>
