<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn4z48ype.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn4z48ype"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rail-symbol" {...props}></Icon>
