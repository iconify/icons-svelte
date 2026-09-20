<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isu_57j9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isu_57j9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:git-commit" {...props}></Icon>
