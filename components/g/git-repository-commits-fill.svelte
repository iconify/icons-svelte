<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mui5-zbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mui5-zbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-repository-commits-fill" {...props}></Icon>
