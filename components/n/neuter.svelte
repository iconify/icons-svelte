<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d27n0hbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":24};
const content = `<path class="d27n0hbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:neuter" {...props}></Icon>
