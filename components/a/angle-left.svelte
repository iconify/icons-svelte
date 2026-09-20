<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd_4pkbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd_4pkbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:angle-left" {...props}></Icon>
