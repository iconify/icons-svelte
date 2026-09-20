<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoz_nywhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoz_nywhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:motorbike-package" {...props}></Icon>
