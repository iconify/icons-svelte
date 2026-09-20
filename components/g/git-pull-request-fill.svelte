<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmyl__bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmyl__bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-pull-request-fill" {...props}></Icon>
