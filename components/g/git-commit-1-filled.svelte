<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oulhdmbyw.css';
import '../../css/i/iuiai5bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oulhdmbyw"/><path class="iuiai5bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:git-commit-1-filled" {...props}></Icon>
