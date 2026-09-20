<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzg21tuzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzg21tuzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:questionnaire-line" {...props}></Icon>
