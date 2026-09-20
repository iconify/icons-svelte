<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko7wmu2ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko7wmu2ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:align-center-justify" {...props}></Icon>
