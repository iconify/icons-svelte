<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc2sj5asw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc2sj5asw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dice-5-fill" {...props}></Icon>
