<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0s77uk3v.css';
import '../../css/o/oclompb7u.css';
import '../../css/y/y-ttjwi6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0s77uk3v"/><circle class="oclompb7u"/><path class="y-ttjwi6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:exclamation-triangle" {...props}></Icon>
