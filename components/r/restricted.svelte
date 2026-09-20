<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n312wjbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n312wjbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:restricted" {...props}></Icon>
