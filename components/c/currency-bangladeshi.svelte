<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oca-jxbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oca-jxbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:currency-bangladeshi" {...props}></Icon>
