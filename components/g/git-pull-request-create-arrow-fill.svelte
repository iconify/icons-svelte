<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peznxynyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="peznxynyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-pull-request-create-arrow-fill" {...props}></Icon>
