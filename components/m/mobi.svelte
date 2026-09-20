<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmzcyxbor.css';
import '../../css/c/cdw1yt0dr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmzcyxbor"/><path class="cdw1yt0dr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mobi" {...props}></Icon>
