<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv52a4buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cv52a4buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:floor-lamp2" {...props}></Icon>
