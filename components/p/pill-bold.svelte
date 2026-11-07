<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl_-elx9a.css';
import '../../css/k/ky59n46dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl_-elx9a"/><path class="ky59n46dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pill-bold" {...props}></Icon>
