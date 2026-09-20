<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncphwmyrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncphwmyrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:radio-2-line" {...props}></Icon>
