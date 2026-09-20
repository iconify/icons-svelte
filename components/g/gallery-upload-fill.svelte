<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k70dj_bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k70dj_bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gallery-upload-fill" {...props}></Icon>
