<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7zzkzb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7zzkzb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:color-picker" {...props}></Icon>
