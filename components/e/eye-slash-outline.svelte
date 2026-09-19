<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7zzptsss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7zzptsss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:eye-slash-outline" {...props}></Icon>
