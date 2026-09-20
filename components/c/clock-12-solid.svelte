<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpgziacym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpgziacym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-12-solid" {...props}></Icon>
